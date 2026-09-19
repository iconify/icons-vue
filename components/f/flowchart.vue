<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvk_bnbme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="xvk_bnbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:flowchart" /></template>
