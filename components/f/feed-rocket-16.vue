<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9crslb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c9crslb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:feed-rocket-16" /></template>
