<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc5gbb7ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mc5gbb7ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:fill-drip" /></template>
