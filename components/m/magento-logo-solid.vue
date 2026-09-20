<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_5lo_lk.css';
import '../../css/o/opmfvvg-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ce_5lo_lk"/><path class="opmfvvg-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:magento-logo-solid" /></template>
