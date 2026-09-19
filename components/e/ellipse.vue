<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcwutrxfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="kcwutrxfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ellipse" /></template>
