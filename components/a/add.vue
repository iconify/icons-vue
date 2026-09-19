<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d47xi2b9o.css';
import '../../css/i/i0hgwgo2s.css';
import '../../css/q/qyzpgohqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="i0hgwgo2s"/><path class="qyzpgohqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:add" /></template>
