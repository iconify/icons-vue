<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvv_3bcke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvv_3bcke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-right-small-round" /></template>
