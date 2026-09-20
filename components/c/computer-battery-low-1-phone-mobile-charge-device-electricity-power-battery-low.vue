<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbn03r-oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zbn03r-oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:computer-battery-low-1-phone-mobile-charge-device-electricity-power-battery-low" /></template>
