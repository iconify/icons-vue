<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soa5_dbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soa5_dbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:indian-super-league" /></template>
