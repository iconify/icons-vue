<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnfa8zd7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bnfa8zd7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:exclamation-mark" /></template>
