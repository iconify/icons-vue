<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbgpe8b5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rbgpe8b5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:circle-16-solid" /></template>
