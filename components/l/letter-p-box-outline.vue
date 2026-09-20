<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw3alhbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rw3alhbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-p-box-outline" /></template>
