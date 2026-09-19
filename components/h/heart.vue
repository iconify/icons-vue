<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8sh02bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8sh02bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:heart" /></template>
