<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6rd7o3ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6rd7o3ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-shared-fill" /></template>
