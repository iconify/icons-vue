<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvcnhi5qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvcnhi5qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googleearthengine" /></template>
