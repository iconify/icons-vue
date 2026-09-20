<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yov6v4b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yov6v4b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:curly-brackets-bold" /></template>
