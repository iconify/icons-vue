<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esmwj4b3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="esmwj4b3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:flag" /></template>
