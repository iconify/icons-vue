<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvg0gs5tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvg0gs5tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-sort-horizontal-sharp" /></template>
