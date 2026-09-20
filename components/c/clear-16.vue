<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbc1sobbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bbc1sobbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:clear-16" /></template>
