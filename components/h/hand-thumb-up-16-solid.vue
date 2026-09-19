<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh5w-s1iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sh5w-s1iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hand-thumb-up-16-solid" /></template>
