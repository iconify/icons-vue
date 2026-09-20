<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt53-_mit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt53-_mit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:atlassian-logo" /></template>
