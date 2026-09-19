<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbcu3ob4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jbcu3ob4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:linkedin-fill-16" /></template>
