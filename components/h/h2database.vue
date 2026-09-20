<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrs-59bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrs-59bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:h2database" /></template>
