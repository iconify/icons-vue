<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmwvu5eco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmwvu5eco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:chevron-right-double" /></template>
