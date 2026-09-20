<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no5pizbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="no5pizbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:frame-outline" /></template>
