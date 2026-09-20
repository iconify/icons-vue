<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbu26itox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lbu26itox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory-16" /></template>
