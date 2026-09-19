<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5hy1lvhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z5hy1lvhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:loudspeaker" /></template>
