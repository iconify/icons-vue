<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqg0u_ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqg0u_ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-dashed-panel-sharp-fill" /></template>
