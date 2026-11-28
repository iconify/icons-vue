<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt7c_7kbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt7c_7kbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:bluetooth-x" /></template>
