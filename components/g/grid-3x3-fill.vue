<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4fzh6b-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4fzh6b-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-3x3-fill" /></template>
