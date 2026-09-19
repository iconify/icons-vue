<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrlytoj6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xrlytoj6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ellipsis-horizontal-16-solid" /></template>
