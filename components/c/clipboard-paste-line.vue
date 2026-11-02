<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay5-2y51q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay5-2y51q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clipboard-paste-line" /></template>
