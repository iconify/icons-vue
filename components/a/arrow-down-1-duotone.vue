<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-gd-sbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-gd-sbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-1-duotone" /></template>
