<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv_90lbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv_90lbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-r-small" /></template>
