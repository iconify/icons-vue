<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdidb4b8e.css';
import '../../css/j/jt195abqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zdidb4b8e"/><path clip-rule="evenodd" class="jt195abqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:header-16" /></template>
