<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7o3m7bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r7o3m7bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:flipboard" /></template>
