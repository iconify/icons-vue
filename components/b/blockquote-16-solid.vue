<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqnlckxzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tqnlckxzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:blockquote-16-solid" /></template>
