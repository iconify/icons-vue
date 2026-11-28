<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynz9ybc5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynz9ybc5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:ev-charger" /></template>
