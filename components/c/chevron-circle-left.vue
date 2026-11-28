<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9mkogbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9mkogbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chevron-circle-left" /></template>
