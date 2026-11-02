<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_aruvb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_aruvb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:celebrate-line" /></template>
