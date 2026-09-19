<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8gmqq-tp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j8gmqq-tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-sleet" /></template>
