<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irz_gyb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="irz_gyb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:forward-10-fill" /></template>
