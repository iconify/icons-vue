<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijk9gbbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ijk9gbbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:api" /></template>
