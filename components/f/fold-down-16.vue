<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w05rj732j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w05rj732j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fold-down-16" /></template>
