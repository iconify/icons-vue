<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxrvpzbit.css';
import '../../css/o/ob_nbubvj.css';
import '../../css/s/svdy80z7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dxrvpzbit"/><circle class="ob_nbubvj"/><path class="svdy80z7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:accessibility-alt" /></template>
