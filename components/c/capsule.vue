<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_xr55c6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="q_xr55c6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:capsule" /></template>
