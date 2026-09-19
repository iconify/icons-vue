<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrbjelblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrbjelblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-pressure-monitor-24px" /></template>
