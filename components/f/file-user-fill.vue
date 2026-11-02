<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ex35hwhyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex35hwhyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:file-user-fill" /></template>
