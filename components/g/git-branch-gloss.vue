<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl26vvbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl26vvbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-branch-gloss" /></template>
