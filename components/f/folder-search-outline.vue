<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9-8otbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9-8otbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-search-outline" /></template>
