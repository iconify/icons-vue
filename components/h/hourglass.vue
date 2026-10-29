<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdhdh5hpt.css';
import '../../css/k/keuh4feao.css';
import '../../css/h/hu_cubcac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdhdh5hpt"/><path class="keuh4feao"/><path class="hu_cubcac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:hourglass" /></template>
