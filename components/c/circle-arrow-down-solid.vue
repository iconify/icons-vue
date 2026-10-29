<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uns0k8ioc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uns0k8ioc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-arrow-down-solid" /></template>
