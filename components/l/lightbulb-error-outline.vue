<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edfyd8sst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edfyd8sst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-error-outline" /></template>
