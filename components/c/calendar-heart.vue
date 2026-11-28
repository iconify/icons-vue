<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6fr_n7rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6fr_n7rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calendar-heart" /></template>
