<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk0o3qbly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zk0o3qbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-plus-16-solid" /></template>
