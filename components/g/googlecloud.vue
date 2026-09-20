<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxubckb9w.css';
import '../../css/n/nbl00ebkt.css';
import '../../css/w/wtyrvmbzc.css';
import '../../css/h/hr-360lqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxubckb9w"/><path class="nbl00ebkt"/><path class="wtyrvmbzc"/><path class="hr-360lqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:googlecloud" /></template>
