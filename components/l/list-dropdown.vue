<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhomschgd.css';
import '../../css/m/mz1wsz5pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jhomschgd"/><path class="mz1wsz5pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:list-dropdown" /></template>
