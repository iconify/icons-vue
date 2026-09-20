<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrx6ypb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rrx6ypb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:credit-card-16" /></template>
