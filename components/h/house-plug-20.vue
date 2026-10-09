<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpx9c7b2s.css';
import '../../css/p/pc2anacvy.css';
import '../../css/h/hkv3ewbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rpx9c7b2s"/><path class="pc2anacvy"/><path class="hkv3ewbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-plug-20" /></template>
