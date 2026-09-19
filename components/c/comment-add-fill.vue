<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9f4uzbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9f4uzbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-add-fill" /></template>
