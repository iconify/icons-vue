<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htlf_ccgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htlf_ccgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:comsol" /></template>
