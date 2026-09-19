<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zmwq3spqd.css';
import '../../css/t/tqywrzb5u.css';
import '../../css/t/tdq4jhbph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zmwq3spqd"/><path class="tqywrzb5u"/><path class="tdq4jhbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:album-open" /></template>
