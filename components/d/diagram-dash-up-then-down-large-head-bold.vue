<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj9vmwbgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nj9vmwbgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:diagram-dash-up-then-down-large-head-bold" /></template>
