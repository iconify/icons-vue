<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drhte3_lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="drhte3_lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-help-customer-support-4-customer-headset-help-phone-support" /></template>
