<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_nc-k5jc.css';
import '../../css/b/b9b858bmv.css';
import '../../css/t/tplhgkhuc.css';
import '../../css/l/lupdytbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a_nc-k5jc"/><path class="b9b858bmv"/><path class="tplhgkhuc"/><path class="lupdytbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:data-centre-20-bold" /></template>
