<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-wc1tbbt.css';
import '../../css/o/ozoz27b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k-wc1tbbt"/><path class="ozoz27b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chat-bubble-left-right-16-solid" /></template>
