<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzrgs8b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzrgs8b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-image" /></template>
