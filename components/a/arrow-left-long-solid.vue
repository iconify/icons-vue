<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me6qoeb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me6qoeb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-left-long-solid" /></template>
