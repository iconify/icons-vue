<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4wfhlbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4wfhlbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chart-multiple" /></template>
