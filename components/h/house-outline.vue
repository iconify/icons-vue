<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icl41xlnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="icl41xlnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:house-outline" /></template>
