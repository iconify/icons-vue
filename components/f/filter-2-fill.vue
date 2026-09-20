<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnosb5bey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnosb5bey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:filter-2-fill" /></template>
