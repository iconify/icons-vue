<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbo646wjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jbo646wjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-down-arrow-up" /></template>
