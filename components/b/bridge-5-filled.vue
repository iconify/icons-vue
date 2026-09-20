<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m76uv7b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m76uv7b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bridge-5-filled" /></template>
