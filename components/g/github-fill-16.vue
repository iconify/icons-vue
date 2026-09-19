<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goo9ribrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="goo9ribrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:github-fill-16" /></template>
