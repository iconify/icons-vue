<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlgtlvbnh.css';
import '../../css/r/rghwx5e1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlgtlvbnh"/><path class="rghwx5e1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:amazon-pay" /></template>
