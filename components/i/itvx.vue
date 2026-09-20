<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1_bu3b6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1_bu3b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:itvx" /></template>
