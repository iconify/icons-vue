<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfkcbob-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":733,"height":1024};
const content = `<path class="cfkcbob-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:candycane" /></template>
