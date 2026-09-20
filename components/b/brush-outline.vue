<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt_crccnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt_crccnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:brush-outline" /></template>
