<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6pddwiwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6pddwiwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:comment-2" /></template>
