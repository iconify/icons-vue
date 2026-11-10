<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsrof7c5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zsrof7c5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-check-16-solid" /></template>
