<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5pa9of_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5pa9of_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:easter" /></template>
