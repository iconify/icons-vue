<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axlz7bb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axlz7bb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:expand-less-fill" /></template>
