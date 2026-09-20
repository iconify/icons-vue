<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f60vnpbnl.css';
import '../../css/i/iv6-xf8hg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f60vnpbnl"/><path class="iv6-xf8hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:items-list-16" /></template>
