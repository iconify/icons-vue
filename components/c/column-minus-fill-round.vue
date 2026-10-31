<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukcc3lbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukcc3lbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:column-minus-fill-round" /></template>
