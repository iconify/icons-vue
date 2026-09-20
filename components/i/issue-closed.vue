<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak0zltcte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ak0zltcte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-closed" /></template>
