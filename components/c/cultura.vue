<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu1cwab2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu1cwab2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cultura" /></template>
