<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtsvcgbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtsvcgbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:building-check" /></template>
