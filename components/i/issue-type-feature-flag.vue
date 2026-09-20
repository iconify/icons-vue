<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haor4_unv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="haor4_unv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-type-feature-flag" /></template>
