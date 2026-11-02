<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg9jf2aku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9jf2aku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-branch-2-fill" /></template>
