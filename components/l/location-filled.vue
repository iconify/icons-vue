<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swq55bbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="swq55bbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:location-filled" /></template>
