<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgamf5ziv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgamf5ziv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:document-windows" /></template>
