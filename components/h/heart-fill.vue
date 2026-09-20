<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsdlbfb4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsdlbfb4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:heart-fill" /></template>
