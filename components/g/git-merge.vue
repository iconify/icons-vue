<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjreeci1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kjreeci1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:git-merge" /></template>
