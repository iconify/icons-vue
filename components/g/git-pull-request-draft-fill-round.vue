<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx2kf4bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wx2kf4bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-pull-request-draft-fill-round" /></template>
