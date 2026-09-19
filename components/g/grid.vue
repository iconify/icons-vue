<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in_je1b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in_je1b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:grid" /></template>
