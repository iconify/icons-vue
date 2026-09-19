<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez4hw9bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ez4hw9bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:desk-lamp" /></template>
