<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf06q3b-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf06q3b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:globe-check" /></template>
