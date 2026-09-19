<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j407f1bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="j407f1bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lifebuoy-16-solid" /></template>
