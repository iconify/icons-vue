<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxbwv0bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxbwv0bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-upload-outline" /></template>
