<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckwu9ub3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ckwu9ub3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:call-16" /></template>
