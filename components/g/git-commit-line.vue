<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt7zskbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt7zskbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-commit-line" /></template>
