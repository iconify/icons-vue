<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4kyeqb6q.css';
import '../../css/x/xmhb8kgbl.css';
import '../../css/w/wsnj7ybey.css';
import '../../css/s/sbrtnw41k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4kyeqb6q wm-a"/><path class="wm-a xmhb8kgbl"/><path class="wm-k wsnj7ybey"/><path class="sbrtnw41k wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:chevrons-right" /></template>
