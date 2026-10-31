<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpbcez6dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpbcez6dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:help-circle-gloss" /></template>
