<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvkok9nbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvkok9nbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:comment-close-bold" /></template>
