<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svd2s_bjj.css';
import '../../css/e/ese12xb1h.css';
import '../../css/h/huatr0-xh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="svd2s_bjj"/><path class="ese12xb1h"/><path class="huatr0-xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-hearing-assistance" /></template>
