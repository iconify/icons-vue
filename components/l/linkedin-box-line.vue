<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpno3-vgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpno3-vgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:linkedin-box-line" /></template>
