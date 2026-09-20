<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5lhsu95r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5lhsu95r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-outline" /></template>
