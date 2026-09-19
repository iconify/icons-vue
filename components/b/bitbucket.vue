<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8wydab-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j8wydab-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:bitbucket" /></template>
