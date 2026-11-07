<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_wb8jbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d_wb8jbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-minimalistic-outline" /></template>
