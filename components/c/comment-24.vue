<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_2ax6o9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_2ax6o9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:comment-24" /></template>
