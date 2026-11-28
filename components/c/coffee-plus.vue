<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhmjpjbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhmjpjbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:coffee-plus" /></template>
