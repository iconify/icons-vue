<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2dx9kmgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2dx9kmgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:battery-2-charge-line" /></template>
