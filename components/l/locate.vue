<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm__iwh4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm__iwh4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:locate" /></template>
