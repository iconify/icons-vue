<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zrpmm7bkk.css';
import '../../css/q/qqtepqb8i.css';
import '../../css/l/luu53hbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zrpmm7bkk"/><path class="qqtepqb8i"/><path class="luu53hbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:exit-broken" /></template>
