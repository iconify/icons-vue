<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8q5547tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8q5547tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-edit-outline" /></template>
