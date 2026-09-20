<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by6okx3ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by6okx3ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-won-2-line" /></template>
