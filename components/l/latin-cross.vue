<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii1rvbbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ii1rvbbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:latin-cross" /></template>
