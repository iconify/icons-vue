<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc8gq2dqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc8gq2dqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-compare-filled" /></template>
