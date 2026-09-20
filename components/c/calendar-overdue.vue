<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1623dbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j1623dbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:calendar-overdue" /></template>
