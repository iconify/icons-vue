<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obit9z1kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obit9z1kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:cake" /></template>
