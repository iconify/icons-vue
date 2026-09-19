<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzf93bbes.css';
import '../../css/f/fy34vxb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzf93bbes"/><path clip-rule="evenodd" class="fy34vxb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:copy-outline" /></template>
