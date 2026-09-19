<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj4ta2cbo.css';
import '../../css/t/t4yq35mvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yj4ta2cbo"/><path class="t4yq35mvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:location-star-filled" /></template>
