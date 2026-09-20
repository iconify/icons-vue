<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/krumclx4i.css';
import '../../css/n/nvoqp-sdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":64};
const content = `<path class="krumclx4i"/><path class="nvoqp-sdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-alternative-complementary" /></template>
