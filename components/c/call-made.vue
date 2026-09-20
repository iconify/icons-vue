<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxolemb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxolemb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:call-made" /></template>
