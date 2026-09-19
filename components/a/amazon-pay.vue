<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2kp-dbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m2kp-dbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:amazon-pay" /></template>
