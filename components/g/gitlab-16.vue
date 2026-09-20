<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h3m-0_wes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h3m-0_wes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:gitlab-16" /></template>
