<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2niyf_kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2niyf_kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-open" /></template>
