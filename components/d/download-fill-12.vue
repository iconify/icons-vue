<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2xsqtgqd.css';
import '../../css/p/pdd2_pbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t2xsqtgqd"/><path class="pdd2_pbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:download-fill-12" /></template>
