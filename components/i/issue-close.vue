<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0gmuvb4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x0gmuvb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-close" /></template>
