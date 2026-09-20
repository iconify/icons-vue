<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwc74hgmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lwc74hgmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-location-outline" /></template>
