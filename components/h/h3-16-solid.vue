<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqeqx7bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bqeqx7bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h3-16-solid" /></template>
