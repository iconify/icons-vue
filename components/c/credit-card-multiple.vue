<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hff65g63h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="hff65g63h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:credit-card-multiple" /></template>
