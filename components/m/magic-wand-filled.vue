<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2mnm_bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2mnm_bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:magic-wand-filled" /></template>
