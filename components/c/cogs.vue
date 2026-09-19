<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk-r7jbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bk-r7jbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:cogs" /></template>
