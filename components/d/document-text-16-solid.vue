<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztazg6i9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ztazg6i9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-text-16-solid" /></template>
