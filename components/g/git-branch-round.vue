<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5k9y5r3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5k9y5r3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:git-branch-round" /></template>
