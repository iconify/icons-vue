<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t58ktzpqn.css';
import '../../css/h/hai_nbocs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t58ktzpqn"/><path clip-rule="evenodd" class="hai_nbocs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:instagram-fill-16" /></template>
