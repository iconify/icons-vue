<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-rrygmvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n-rrygmvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-arrow-down-16-solid" /></template>
