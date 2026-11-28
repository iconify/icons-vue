<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srxrgzi5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srxrgzi5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:coffee-x" /></template>
