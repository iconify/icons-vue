<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-c7-4b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-c7-4b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-settings-corner-round" /></template>
