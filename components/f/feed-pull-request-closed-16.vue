<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxiz10l3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bxiz10l3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-pull-request-closed-16" /></template>
