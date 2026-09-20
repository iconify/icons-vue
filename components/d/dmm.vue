<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7qfvb_xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7qfvb_xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dmm" /></template>
