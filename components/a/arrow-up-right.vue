<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/godq996fe.css';
import '../../css/w/wxmbpuu5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="godq996fe wm-k"/><path class="wm-a wxmbpuu5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:arrow-up-right" /></template>
