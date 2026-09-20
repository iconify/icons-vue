<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiwt2mb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tiwt2mb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-branch-outline" /></template>
