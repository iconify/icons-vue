<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdsz5c2ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdsz5c2ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:business-deal-cash-2" /></template>
