<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsmsj-9cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nsmsj-9cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:heart-filled" /></template>
