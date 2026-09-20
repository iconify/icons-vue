<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_uvk0s-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_uvk0s-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:loop-1-flat" /></template>
