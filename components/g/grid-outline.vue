<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ort_5xell.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ort_5xell"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:grid-outline" /></template>
