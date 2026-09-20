<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5gqkoe1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5gqkoe1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-connect" /></template>
