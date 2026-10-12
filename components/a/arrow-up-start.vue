<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttki8ltre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttki8ltre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrow-up-start" /></template>
