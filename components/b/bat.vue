<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1m5ykyav.css';
import '../../css/u/uylh2bc2i.css';
import '../../css/w/wuyl63pyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1m5ykyav wm-k"/><path class="uylh2bc2i wm-a"/><path class="wm-a wuyl63pyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bat" /></template>
