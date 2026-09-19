<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zksklzbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zksklzbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:book-open-20-solid" /></template>
