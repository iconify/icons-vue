<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekpgxptpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ekpgxptpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:dog-sitting-wearing-harness-and-whistle" /></template>
