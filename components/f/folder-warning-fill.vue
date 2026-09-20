<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v50-1gblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v50-1gblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-warning-fill" /></template>
