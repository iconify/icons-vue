<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh_3csxda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh_3csxda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-pull-request-filled" /></template>
