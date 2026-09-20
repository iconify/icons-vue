<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9j16-bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9j16-bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:briefcase-16" /></template>
