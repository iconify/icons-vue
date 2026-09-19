<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bck-16bdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bck-16bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-arrow-down" /></template>
