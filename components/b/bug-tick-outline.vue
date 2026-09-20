<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyes79och.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyes79och"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bug-tick-outline" /></template>
