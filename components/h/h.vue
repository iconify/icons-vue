<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgr5pjbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kgr5pjbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:h" /></template>
