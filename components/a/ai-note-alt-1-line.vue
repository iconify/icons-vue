<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtkfzdb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtkfzdb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-note-alt-1-line" /></template>
