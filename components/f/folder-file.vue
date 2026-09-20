<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxu7n6der.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxu7n6der"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-file" /></template>
