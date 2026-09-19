<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e8pb5pdno.css';
import '../../css/j/jxst5l4bq.css';
import '../../css/i/in4dbducl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e8pb5pdno"/><path class="jxst5l4bq"/><path class="in4dbducl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:alien-02" /></template>
