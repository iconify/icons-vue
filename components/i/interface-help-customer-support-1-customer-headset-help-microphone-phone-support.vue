<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjm12_boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sjm12_boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-help-customer-support-1-customer-headset-help-microphone-phone-support" /></template>
