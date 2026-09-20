<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_ix4cchu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b_ix4cchu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lock-outline" /></template>
