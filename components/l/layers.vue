<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcwpmsm0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcwpmsm0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layers" /></template>
