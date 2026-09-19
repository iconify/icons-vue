<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezryhh6rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ezryhh6rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:clipboard-fill" /></template>
