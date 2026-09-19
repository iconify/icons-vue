<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loqafrfoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="loqafrfoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:book-mark-outline" /></template>
