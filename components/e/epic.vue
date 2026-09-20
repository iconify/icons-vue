<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6smpr0kq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j6smpr0kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:epic" /></template>
