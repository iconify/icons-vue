<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6hz25pdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6hz25pdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:comment-dots" /></template>
