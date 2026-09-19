<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhox2tbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhox2tbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:kitchen-tools" /></template>
