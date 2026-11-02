<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lka0l_80a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lka0l_80a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-branch-2-line" /></template>
