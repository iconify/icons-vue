<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ky4lymv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ky4lymv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:basket-unfill" /></template>
