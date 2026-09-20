<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrxu82zuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrxu82zuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:eyedropper" /></template>
