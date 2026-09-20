<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1kw9kk6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1kw9kk6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cloud-sync" /></template>
