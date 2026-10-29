<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_y4-6bvi.css';
import '../../css/v/va16dh44j.css';
import '../../css/l/lxbf6jb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_y4-6bvi wm-shadow"/><path class="va16dh44j wm-k"/><path class="lxbf6jb8n wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:braces" /></template>
