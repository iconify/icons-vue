<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5uc7i-cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g5uc7i-cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:filetype-sh" /></template>
