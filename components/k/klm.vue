<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzt8752op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzt8752op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:klm" /></template>
