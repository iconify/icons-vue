<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym6sqko_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ym6sqko_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-symlink-solid" /></template>
