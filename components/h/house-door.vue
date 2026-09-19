<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak8bbzg-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ak8bbzg-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:house-door" /></template>
