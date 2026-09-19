<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cimb_3brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cimb_3brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:lightning-bolt" /></template>
