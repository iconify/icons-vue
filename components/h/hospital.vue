<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v250d_hni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v250d_hni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:hospital" /></template>
