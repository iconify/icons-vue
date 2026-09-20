<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_eddrbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m_eddrbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-mute-notifications" /></template>
