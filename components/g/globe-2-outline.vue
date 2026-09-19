<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4uiwhjsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4uiwhjsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:globe-2-outline" /></template>
