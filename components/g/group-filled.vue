<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrfi2tgtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrfi2tgtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:group-filled" /></template>
