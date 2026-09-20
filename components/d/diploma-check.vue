<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akpl_7g_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="akpl_7g_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:diploma-check" /></template>
