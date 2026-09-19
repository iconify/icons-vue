<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ei-d5jmkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ei-d5jmkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:clear-all" /></template>
