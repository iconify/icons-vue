<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntog37p6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntog37p6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:document" /></template>
