<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v42uykb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v42uykb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-alt-lines" /></template>
