<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiy_99hiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xiy_99hiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-open-m" /></template>
