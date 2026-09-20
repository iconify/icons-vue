<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4q6x8k5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c4q6x8k5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fullscreen-circle" /></template>
