<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw31vrbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zw31vrbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hashtag-16-solid" /></template>
