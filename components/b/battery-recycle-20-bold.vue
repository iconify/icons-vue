<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwtuwobgt.css';
import '../../css/n/n6oa-n9kh.css';
import '../../css/a/azbjuwumn.css';
import '../../css/a/at4icdc8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xwtuwobgt"/><path class="n6oa-n9kh"/><path class="azbjuwumn"/><path class="at4icdc8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-recycle-20-bold" /></template>
