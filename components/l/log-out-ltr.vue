<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2mfls2pl.css';
import '../../css/v/v9ltn1t8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v2mfls2pl"/><path class="v9ltn1t8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:log-out-ltr" /></template>
