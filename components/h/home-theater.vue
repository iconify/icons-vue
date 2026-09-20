<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adjjkwpmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adjjkwpmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-theater" /></template>
