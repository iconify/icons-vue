<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8zb72b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8zb72b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-arrow-right" /></template>
