<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm_qsybka.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/b/bm_iryb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm_qsybka"/><path class="bwibdw4bb"/><path class="bm_iryb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:happy-beaming" /></template>
