<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sm9jy4ulr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sm9jy4ulr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-cog" /></template>
