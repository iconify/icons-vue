<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkelhvzor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bkelhvzor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-type-task" /></template>
