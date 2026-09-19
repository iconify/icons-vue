<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<polygon points="9.25 1.75 2.75 9.25 7.25 9.75 6.75 14.25 13.25 6.75 8.75 6.25" class="hntgybcog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:lightning-bolt" /></template>
