<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlhsgq-gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlhsgq-gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cake-heart" /></template>
