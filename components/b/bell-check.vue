<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqzdhfbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqzdhfbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-check" /></template>
