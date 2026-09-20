<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok0humyuz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok0humyuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fruit-watermelon" /></template>
