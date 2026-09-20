<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2xcm6bdm.css';
import '../../css/q/qp-ml_bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2xcm6bdm"/><path class="qp-ml_bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:cloud-download" /></template>
