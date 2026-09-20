<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaoh63bkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="zaoh63bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:home-alt" /></template>
