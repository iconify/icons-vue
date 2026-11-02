<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m29_9ds_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m29_9ds_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-info-line" /></template>
