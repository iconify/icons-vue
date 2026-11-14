<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqm-b-osx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqm-b-osx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:hourglass" /></template>
