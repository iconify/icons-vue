<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbplw8bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbplw8bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-branch-2-fill" /></template>
