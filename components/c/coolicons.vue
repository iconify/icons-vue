<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovlevwbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovlevwbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:coolicons" /></template>
