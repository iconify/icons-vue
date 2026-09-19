<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlbjazb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlbjazb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:arrow-left-down" /></template>
