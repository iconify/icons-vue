<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsn6_vzwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nsn6_vzwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-left-from-line" /></template>
