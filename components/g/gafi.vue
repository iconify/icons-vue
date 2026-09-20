<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcqs888_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcqs888_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gafi" /></template>
