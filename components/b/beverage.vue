<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj4omabni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vj4omabni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:beverage" /></template>
