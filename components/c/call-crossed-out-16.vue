<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ura_37b8i.css';
import '../../css/y/y71wou8xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ura_37b8i"/><path class="y71wou8xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:call-crossed-out-16" /></template>
