<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sb3ybbs_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sb3ybbs_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:credit-card" /></template>
