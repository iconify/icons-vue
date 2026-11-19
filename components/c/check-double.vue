<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nplz0_bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nplz0_bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:check-double" /></template>
