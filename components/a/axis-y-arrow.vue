<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erw24lbsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="erw24lbsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:axis-y-arrow" /></template>
