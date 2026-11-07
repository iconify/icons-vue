<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/my5268blj.css';
import '../../css/a/a6jo9qb1m.css';
import '../../css/n/ndq0ugbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="my5268blj"/><path class="a6jo9qb1m"/><path class="ndq0ugbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-add-broken" /></template>
