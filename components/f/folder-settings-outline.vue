<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tna48lgfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tna48lgfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-settings-outline" /></template>
