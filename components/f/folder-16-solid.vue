<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0-5aw7dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r0-5aw7dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-16-solid" /></template>
