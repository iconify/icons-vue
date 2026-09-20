<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em6mc21uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em6mc21uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:call" /></template>
