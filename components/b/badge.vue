<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uucv2_foa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uucv2_foa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge" /></template>
