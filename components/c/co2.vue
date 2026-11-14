<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_em85nnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_em85nnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:co2" /></template>
