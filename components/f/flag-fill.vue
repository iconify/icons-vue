<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7sfqwk7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b7sfqwk7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:flag-fill" /></template>
