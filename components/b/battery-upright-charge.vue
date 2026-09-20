<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn-2mgv2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qn-2mgv2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:battery-upright-charge" /></template>
