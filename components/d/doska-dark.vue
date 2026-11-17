<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qebs_l2bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qebs_l2bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doska-dark" /></template>
