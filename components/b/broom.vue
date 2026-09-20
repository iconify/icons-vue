<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb-ueccsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb-ueccsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:broom" /></template>
