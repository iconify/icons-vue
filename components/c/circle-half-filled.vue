<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bavkt7crj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bavkt7crj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:circle-half-filled" /></template>
