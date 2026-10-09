<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1vu9wbcv.css';
import '../../css/a/ab_3yebvn.css';
import '../../css/o/os-dp_ruu.css';
import '../../css/c/cg676jb6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1vu9wbcv"/><path class="ab_3yebvn"/><path class="os-dp_ruu"/><path class="cg676jb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-dashboard-20" /></template>
