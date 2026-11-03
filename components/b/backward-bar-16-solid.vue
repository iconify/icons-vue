<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c74e8fbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c74e8fbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:backward-bar-16-solid" /></template>
