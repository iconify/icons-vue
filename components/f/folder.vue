<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<polygon points="1.75 2.75 1.75 13.25 14.25 13.25 14.25 4.75 8.25 4.75 6.75 2.75" class="hntgybcog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:folder" /></template>
