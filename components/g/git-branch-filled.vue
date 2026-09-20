<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpejmeb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpejmeb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:git-branch-filled" /></template>
