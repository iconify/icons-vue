<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3fmq6b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e3fmq6b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-pull-outline" /></template>
