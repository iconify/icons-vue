<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsr22vg_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsr22vg_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gesture-unlock-fill" /></template>
