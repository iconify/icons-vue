<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm9d3vb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm9d3vb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-ios-back-fill" /></template>
