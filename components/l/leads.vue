<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzy6rmb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzy6rmb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:leads" /></template>
