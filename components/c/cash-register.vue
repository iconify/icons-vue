<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayo0r2bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ayo0r2bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:cash-register" /></template>
