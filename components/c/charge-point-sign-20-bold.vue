<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti01b-i2m.css';
import '../../css/y/yyjf3gxzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ti01b-i2m"/><path class="yyjf3gxzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charge-point-sign-20-bold" /></template>
