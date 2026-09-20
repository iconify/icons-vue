<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkvaydyvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkvaydyvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:langflow" /></template>
