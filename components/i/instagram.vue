<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6jf7qujf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j6jf7qujf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:instagram" /></template>
