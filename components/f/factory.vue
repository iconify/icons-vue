<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zynt9nlma.css';
import '../../css/m/mp8j32oal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zynt9nlma"/><path class="mp8j32oal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:factory" /></template>
