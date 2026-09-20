<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkvup1bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dkvup1bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:grabber-16" /></template>
