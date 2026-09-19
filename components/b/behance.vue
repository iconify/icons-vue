<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y06kbczul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y06kbczul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:behance" /></template>
