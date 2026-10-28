<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix0kzerhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix0kzerhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:currency-azn" /></template>
