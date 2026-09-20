<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fin3fg2wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fin3fg2wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:celestron" /></template>
