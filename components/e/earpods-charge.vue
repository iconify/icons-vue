<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nke5fhnsv.css';
import '../../css/h/hcg_4bble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nke5fhnsv"/><path class="hcg_4bble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:earpods-charge" /></template>
