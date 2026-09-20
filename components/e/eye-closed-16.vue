<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emcctgb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="emcctgb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:eye-closed-16" /></template>
