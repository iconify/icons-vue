<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t24unlyug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="t24unlyug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:2g" /></template>
