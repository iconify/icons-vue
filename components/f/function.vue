<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4fts3b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4fts3b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:function" /></template>
