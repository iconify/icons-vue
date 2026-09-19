<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cilub4bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cilub4bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:jet-fighter-up" /></template>
