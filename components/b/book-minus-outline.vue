<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9z3nfbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9z3nfbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-minus-outline" /></template>
