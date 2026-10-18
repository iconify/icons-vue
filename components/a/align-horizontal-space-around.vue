<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh4c86bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh4c86bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-horizontal-space-around" /></template>
