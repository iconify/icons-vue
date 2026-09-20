<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8djc38rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8djc38rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-branch-fill" /></template>
