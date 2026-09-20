<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c04itccgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="c04itccgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:entrance-10" /></template>
