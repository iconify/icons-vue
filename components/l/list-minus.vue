<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb2uxglrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb2uxglrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:list-minus" /></template>
