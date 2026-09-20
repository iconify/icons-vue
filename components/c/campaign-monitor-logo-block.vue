<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol6h9rdbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol6h9rdbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:campaign-monitor-logo-block" /></template>
