<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aizmdx4bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aizmdx4bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-symlink-outline" /></template>
