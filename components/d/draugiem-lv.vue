<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_b300bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o_b300bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:draugiem-lv" /></template>
