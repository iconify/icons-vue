<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqw3nmqqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uqw3nmqqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:center-16" /></template>
