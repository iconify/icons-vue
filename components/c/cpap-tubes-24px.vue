<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2f-vv4ph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y2f-vv4ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cpap-tubes-24px" /></template>
