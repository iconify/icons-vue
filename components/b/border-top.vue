<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_58pwb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i_58pwb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-top" /></template>
