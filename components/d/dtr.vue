<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/tgf1fixwx.css';
import '../../css/d/d26v317vg.css';
import '../../css/i/iyugarbgj.css';
import '../../css/k/ku63a9bkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="tgf1fixwx"/><g class="d26v317vg"><path class="iyugarbgj"/><path class="ku63a9bkq"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:dtr" /></template>
