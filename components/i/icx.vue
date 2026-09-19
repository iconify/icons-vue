<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt_4t3wrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zt_4t3wrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:icx" /></template>
