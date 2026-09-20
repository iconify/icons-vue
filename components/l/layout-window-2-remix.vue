<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxsyp9bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxsyp9bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:layout-window-2-remix" /></template>
