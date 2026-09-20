<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_8z_56lg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i_8z_56lg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bookmark-16" /></template>
