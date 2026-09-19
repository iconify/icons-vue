<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq7_hjmyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kq7_hjmyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:arrow-up-left" /></template>
