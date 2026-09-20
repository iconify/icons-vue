<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv3lvgb1x.css';
import '../../css/l/ldo0svbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv3lvgb1x"/><path class="ldo0svbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:lock-opened-light" /></template>
