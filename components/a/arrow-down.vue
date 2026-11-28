<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht1an5bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht1an5bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrow-down" /></template>
