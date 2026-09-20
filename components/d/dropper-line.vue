<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v85f75eqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v85f75eqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dropper-line" /></template>
