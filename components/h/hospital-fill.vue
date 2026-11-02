<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw0nn0b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw0nn0b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hospital-fill" /></template>
