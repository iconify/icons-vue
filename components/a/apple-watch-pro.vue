<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0ib1m_ma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0ib1m_ma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple-watch-pro" /></template>
