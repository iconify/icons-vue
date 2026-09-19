<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn9o4mbwr.css';
import '../../css/b/bmx7xbb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tn9o4mbwr"/><path class="bmx7xbb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:cpp-header" /></template>
