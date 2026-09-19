<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gj__wgbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj__wgbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:folder" /></template>
