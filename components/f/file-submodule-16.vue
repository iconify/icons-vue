<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbntjqb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tbntjqb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-submodule-16" /></template>
