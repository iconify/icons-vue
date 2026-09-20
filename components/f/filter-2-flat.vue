<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfc3tf98d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wfc3tf98d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:filter-2-flat" /></template>
