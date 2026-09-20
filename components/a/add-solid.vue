<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcrkei-7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vcrkei-7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:add-solid" /></template>
