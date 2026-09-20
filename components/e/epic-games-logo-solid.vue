<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvu19abye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jvu19abye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:epic-games-logo-solid" /></template>
