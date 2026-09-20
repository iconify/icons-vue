<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abjqn5hlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="abjqn5hlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrow-right-to-rectangle-tall-outline" /></template>
