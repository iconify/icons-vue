<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztme5hbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztme5hbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:folder-music" /></template>
