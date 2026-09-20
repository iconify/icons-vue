<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/otcocxbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otcocxbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-showers-alt" /></template>
