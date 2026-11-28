<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai_m1zzqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai_m1zzqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:folder-open-check" /></template>
