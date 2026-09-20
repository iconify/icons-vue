<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5d033baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5d033baa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:archive-2" /></template>
