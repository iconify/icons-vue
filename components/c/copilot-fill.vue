<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwxmvn-7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwxmvn-7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:copilot-fill" /></template>
