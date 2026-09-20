<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8snzujqw.css';
import '../../css/r/roq1fmb9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f8snzujqw"/><path clip-rule="evenodd" class="roq1fmb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:lock-screen-16" /></template>
