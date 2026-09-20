<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-kjzsbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="v-kjzsbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:arrow-up" /></template>
