<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/metcehf7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="metcehf7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:glasses-filled" /></template>
