<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5jxckb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5jxckb5q"><animateTransform attributeName="transform" attributeType="XML" dur="5s" from="360 12 12" repeatCount="indefinite" to="0 12 12" type="rotate"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:arrow-rotate" /></template>
