<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpy9h52dg.css';
import '../../css/b/b9rr1pb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hpy9h52dg"/><path class="b9rr1pb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-hide" /></template>
