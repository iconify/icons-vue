<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfhs66b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfhs66b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:braces-check" /></template>
