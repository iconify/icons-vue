<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d80swtbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d80swtbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cellular-network-5g" /></template>
