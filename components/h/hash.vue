<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvhmp-bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvhmp-bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:hash" /></template>
