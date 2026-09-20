<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zujkk5zci.css';
import '../../css/e/etr_cu8yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zujkk5zci"/><path class="etr_cu8yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gamepad-button-left-16" /></template>
