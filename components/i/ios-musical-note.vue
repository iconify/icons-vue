<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lucdfsf2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lucdfsf2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-musical-note" /></template>
