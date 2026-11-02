<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw6usabhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw6usabhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:look-left-fill" /></template>
