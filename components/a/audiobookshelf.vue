<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoq6qt-ts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoq6qt-ts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:audiobookshelf" /></template>
