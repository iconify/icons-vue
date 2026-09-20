<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft1qwibcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ft1qwibcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:comment" /></template>
