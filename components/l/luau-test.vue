<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f02hbyofe.css';
import '../../css/b/bm8h3db9m.css';
import '../../css/d/ddmfo5g7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f02hbyofe"/><path class="bm8h3db9m"/><path class="ddmfo5g7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:luau-test" /></template>
