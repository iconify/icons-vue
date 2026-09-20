<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9pzv_bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9pzv_bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:alarm-smoke-solid" /></template>
