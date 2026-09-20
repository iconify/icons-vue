<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7y1xq4zj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b7y1xq4zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:error-16" /></template>
