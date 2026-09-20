<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qf_1fb-pf.css';
import '../../css/p/po8eo_bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qf_1fb-pf"/><path class="po8eo_bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:anchor-top-right-16" /></template>
