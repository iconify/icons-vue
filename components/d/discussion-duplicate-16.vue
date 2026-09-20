<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m90r2bo5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m90r2bo5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:discussion-duplicate-16" /></template>
