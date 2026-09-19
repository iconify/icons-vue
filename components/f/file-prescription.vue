<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6s009bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t6s009bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-prescription" /></template>
