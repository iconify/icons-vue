<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c2m5upb1f.css';
import '../../css/r/rumgkrbdt.css';
import '../../css/y/ye66fobzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c2m5upb1f"/><path class="rumgkrbdt"/><path class="ye66fobzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-broken" /></template>
