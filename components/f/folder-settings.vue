<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuamfw_8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nuamfw_8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-settings" /></template>
