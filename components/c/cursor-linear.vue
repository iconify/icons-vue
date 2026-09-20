<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzy99uvdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzy99uvdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cursor-linear" /></template>
