<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7n8tfqul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x7n8tfqul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-remove-fill" /></template>
