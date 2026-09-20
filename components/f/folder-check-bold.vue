<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su1r-hbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="su1r-hbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-check-bold" /></template>
