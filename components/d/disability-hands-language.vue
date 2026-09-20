<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr3ud21_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jr3ud21_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:disability-hands-language" /></template>
