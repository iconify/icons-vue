<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zic8crbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zic8crbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:basket3-fill" /></template>
