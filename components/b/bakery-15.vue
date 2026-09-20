<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrde4zxpv.css';
import '../../css/m/m-85-0blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qrde4zxpv"/><path class="m-85-0blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bakery-15" /></template>
