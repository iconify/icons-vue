<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s78ivybtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s78ivybtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-edit-fill" /></template>
