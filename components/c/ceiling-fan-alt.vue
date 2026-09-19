<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sspix23by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sspix23by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-fan-alt" /></template>
