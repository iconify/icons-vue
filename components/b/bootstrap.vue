<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_mmg7b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a_mmg7b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:bootstrap" /></template>
