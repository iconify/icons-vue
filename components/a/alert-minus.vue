<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kncpq6wxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kncpq6wxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alert-minus" /></template>
