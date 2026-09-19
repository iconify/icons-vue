<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu6bpab-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fu6bpab-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:github-small" /></template>
