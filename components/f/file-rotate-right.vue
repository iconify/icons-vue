<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptfe_cbys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptfe_cbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-rotate-right" /></template>
