<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzroxwpzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzroxwpzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-diff-line" /></template>
