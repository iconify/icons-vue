<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2yshue7o.css';
import '../../css/e/e1xd40_pr.css';
import '../../css/z/z0rs_mbws.css';
import '../../css/v/vq9d_mwxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t2yshue7o"/><path class="e1xd40_pr"/><path class="z0rs_mbws"/><path class="vq9d_mwxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-inpatient" /></template>
