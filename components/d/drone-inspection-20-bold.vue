<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm9mbi_na.css';
import '../../css/o/ocfy37bnq.css';
import '../../css/e/edls71zqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pm9mbi_na"/><path class="ocfy37bnq"/><path class="edls71zqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:drone-inspection-20-bold" /></template>
