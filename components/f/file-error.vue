<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw7q3l5ax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jw7q3l5ax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:file-error" /></template>
