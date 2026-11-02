<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oee8e_b-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oee8e_b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-octagon-fill" /></template>
