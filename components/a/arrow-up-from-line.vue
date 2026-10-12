<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-sa7-btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-sa7-btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrow-up-from-line" /></template>
