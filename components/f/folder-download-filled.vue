<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-zbrzxta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-zbrzxta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-download-filled" /></template>
