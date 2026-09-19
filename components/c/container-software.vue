<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw59wdbrq.css';
import '../../css/e/eyc11k90x.css';
import '../../css/k/kp_ro9o2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sw59wdbrq"/><path class="eyc11k90x"/><path class="kp_ro9o2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:container-software" /></template>
