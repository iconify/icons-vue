<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbmd_dbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbmd_dbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:die-3" /></template>
