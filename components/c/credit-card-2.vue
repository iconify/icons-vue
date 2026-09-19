<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2u665ban.css';
import '../../css/v/vu8g70hjm.css';
import '../../css/u/uxqzk2bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="vu8g70hjm"/><rect class="uxqzk2bql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:credit-card-2" /></template>
