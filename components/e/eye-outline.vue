<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyh8m0cby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kyh8m0cby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eye-outline" /></template>
