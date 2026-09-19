<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-5uilbhv.css';
import '../../css/i/i2ddjlrtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="m-5uilbhv"/><path class="i2ddjlrtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:id-4x3" /></template>
