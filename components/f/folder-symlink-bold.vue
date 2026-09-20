<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybfag4d8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybfag4d8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-symlink-bold" /></template>
