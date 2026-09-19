<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw23apjax.css';
import '../../css/f/ftl0q4tvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw23apjax"/><path class="ftl0q4tvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-money" /></template>
