<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0zhfqmgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u0zhfqmgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:clock-16" /></template>
