<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a69wlg18g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a69wlg18g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:jinja" /></template>
