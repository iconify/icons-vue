<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c83uhb54j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c83uhb54j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:credit-card-minus" /></template>
