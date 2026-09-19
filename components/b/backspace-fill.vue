<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bua8ano9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bua8ano9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:backspace-fill" /></template>
