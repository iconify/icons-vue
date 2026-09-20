<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4qjz4jhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4qjz4jhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-meh-16-solid" /></template>
