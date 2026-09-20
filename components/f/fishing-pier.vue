<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7i7tqbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="t7i7tqbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:fishing-pier" /></template>
