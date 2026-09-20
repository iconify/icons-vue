<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihvzegruc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihvzegruc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-branch-line" /></template>
