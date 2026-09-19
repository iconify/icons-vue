<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh7z8ib8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh7z8ib8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-left-tag-solid" /></template>
