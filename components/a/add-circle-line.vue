<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uceaikbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uceaikbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:add-circle-line" /></template>
