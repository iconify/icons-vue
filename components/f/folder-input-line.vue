<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oesnb6qqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oesnb6qqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-input-line" /></template>
