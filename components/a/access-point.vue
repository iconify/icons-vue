<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz_0v_mxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz_0v_mxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:access-point" /></template>
