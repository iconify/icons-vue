<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz4zr0-dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zz4zr0-dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:envelope-open-16-solid" /></template>
