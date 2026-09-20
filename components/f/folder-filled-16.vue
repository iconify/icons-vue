<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp71ghbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kp71ghbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:folder-filled-16" /></template>
