<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxsgl8bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxsgl8bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-handle-sharp" /></template>
