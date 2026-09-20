<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/febt9so4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="febt9so4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hourglass-line" /></template>
