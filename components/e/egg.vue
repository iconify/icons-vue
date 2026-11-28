<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0t-jn1ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0t-jn1ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:egg" /></template>
