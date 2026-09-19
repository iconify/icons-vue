<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqz_9obsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqz_9obsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:balcony" /></template>
