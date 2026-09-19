<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl6warb1x.css';
import '../../css/b/bjk_wjbnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl6warb1x"/><path class="bjk_wjbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:location-check" /></template>
