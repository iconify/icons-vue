<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj98ljgyw.css';
import '../../css/y/yw3dmeumf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xj98ljgyw"/><path class="yw3dmeumf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-save" /></template>
