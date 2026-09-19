<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9rqdccvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v9rqdccvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bolt-slash-16-solid" /></template>
