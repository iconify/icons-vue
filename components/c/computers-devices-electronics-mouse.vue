<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5n7r2czb.css';
import '../../css/m/muo8ifbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k5n7r2czb"/><path class="muo8ifbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:computers-devices-electronics-mouse" /></template>
