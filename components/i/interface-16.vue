<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vji_uo4-j.css';
import '../../css/b/bsx5zebbq.css';
import '../../css/q/qb75cnf9c.css';
import '../../css/j/j5c61kb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vji_uo4-j"/><path clip-rule="evenodd" class="bsx5zebbq"/><path class="qb75cnf9c"/><path clip-rule="evenodd" class="j5c61kb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:interface-16" /></template>
