<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ny1sbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ny1sbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kenmei" /></template>
