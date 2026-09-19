<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpkkrabjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpkkrabjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-commit-filled" /></template>
