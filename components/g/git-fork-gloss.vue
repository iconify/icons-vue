<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng1wjts8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1wjts8f wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:git-fork-gloss" /></template>
