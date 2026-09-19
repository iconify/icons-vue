<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et_rd7bsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":999,"height":1000};
const content = `<path class="et_rd7bsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-saint" /></template>
