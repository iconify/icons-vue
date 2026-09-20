<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvp3tpbju.css';
import '../../css/s/sa794qgvp.css';
import '../../css/z/zxq1r2bws.css';
import '../../css/q/qdr1inb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mvp3tpbju"/><path class="sa794qgvp"/><path class="zxq1r2bws"/><path class="qdr1inb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:labelito-dark" /></template>
