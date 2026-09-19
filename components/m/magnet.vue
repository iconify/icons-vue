<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwdw3u4am.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pwdw3u4am"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:magnet" /></template>
