<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz7sa-bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz7sa-bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:folder-close" /></template>
