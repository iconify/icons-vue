<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_0ppdb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_0ppdb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-settings" /></template>
