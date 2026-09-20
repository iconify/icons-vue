<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7uefybns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7uefybns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-arrow-right" /></template>
