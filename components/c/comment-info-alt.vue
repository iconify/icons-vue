<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3kin-b0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3kin-b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-info-alt" /></template>
