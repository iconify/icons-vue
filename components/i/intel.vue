<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr61sd6wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr61sd6wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:intel" /></template>
