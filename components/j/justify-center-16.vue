<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i001kvvwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i001kvvwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:justify-center-16" /></template>
