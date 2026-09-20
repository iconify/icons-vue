<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8-ol_24k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8-ol_24k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-merge-queue-24" /></template>
