<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqp3gcbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqp3gcbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bill-line" /></template>
