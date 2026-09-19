<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwq-xk6uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="bwq-xk6uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-folder-small-filled" /></template>
