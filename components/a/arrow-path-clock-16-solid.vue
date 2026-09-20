<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv_vv6bcm.css';
import '../../css/r/r_8zsvb4v.css';
import '../../css/n/ncs7ab22i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="nv_vv6bcm"><path class="r_8zsvb4v"/><path class="ncs7ab22i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-path-clock-16-solid" /></template>
