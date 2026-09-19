<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c318b6b7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="c318b6b7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:issue" /></template>
