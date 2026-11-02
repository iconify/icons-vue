<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_ooxmpjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_ooxmpjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:keyboard-off-fill" /></template>
