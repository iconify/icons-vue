<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsf_xwbsm.css';
import '../../css/q/qp7v_obxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vsf_xwbsm"/><path class="qp7v_obxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:crop" /></template>
