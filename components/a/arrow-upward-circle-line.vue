<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii897cc6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii897cc6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-upward-circle-line" /></template>
