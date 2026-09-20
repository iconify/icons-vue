<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbuw-_bre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbuw-_bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:credit-card-x" /></template>
