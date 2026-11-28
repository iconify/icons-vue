<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxi8rbh_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oxi8rbh_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:caret-down-up" /></template>
