<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmoieybge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmoieybge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:file-symlink-solid" /></template>
