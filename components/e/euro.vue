<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9ohoulew.css';
import '../../css/r/ro2kipt4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9ohoulew wm-k"/><path class="ro2kipt4k wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:euro" /></template>
