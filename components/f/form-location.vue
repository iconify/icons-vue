<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf87t3b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf87t3b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-location" /></template>
