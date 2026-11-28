<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgee6ac_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tgee6ac_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:check-circle-multiple-bold" /></template>
