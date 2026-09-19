<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmkfoccpl.css';
import '../../css/w/wllfbt0-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-primary-layer fmkfoccpl"/><path class="duoicon-secondary-layer wllfbt0-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:app-dots" /></template>
