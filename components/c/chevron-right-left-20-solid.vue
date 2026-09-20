<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6vvru-gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j6vvru-gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-right-left-20-solid" /></template>
