<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj0y3zbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xj0y3zbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:inbox-fill-16" /></template>
