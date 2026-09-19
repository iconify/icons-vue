<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9q7lubyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b9q7lubyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:behance-square" /></template>
