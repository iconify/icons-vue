<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wo2mc-qtj.css';
import '../../css/e/eopj_5x7f.css';
import '../../css/p/pkxsu9bpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wo2mc-qtj"/><path class="eopj_5x7f"/><path class="pkxsu9bpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-reply-01" /></template>
