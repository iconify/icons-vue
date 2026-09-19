<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9_cr7dkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a9_cr7dkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bone-fracture" /></template>
