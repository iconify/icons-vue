<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if6e8ibdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="if6e8ibdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:circle-chevron-down" /></template>
