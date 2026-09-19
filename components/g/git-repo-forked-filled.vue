<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrakngbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrakngbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-repo-forked-filled" /></template>
