<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lekjeecxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lekjeecxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-plus-fill" /></template>
