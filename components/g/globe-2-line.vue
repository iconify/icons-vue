<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_odc2bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_odc2bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:globe-2-line" /></template>
