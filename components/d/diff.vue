<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl_7wtbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":16};
const content = `<path class="pl_7wtbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diff" /></template>
