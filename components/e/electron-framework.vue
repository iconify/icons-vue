<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwb4_5-np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwb4_5-np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:electron-framework" /></template>
