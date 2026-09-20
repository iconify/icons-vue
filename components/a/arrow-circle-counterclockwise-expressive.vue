<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e187webbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e187webbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-circle-counterclockwise-expressive" /></template>
