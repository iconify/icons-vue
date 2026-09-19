<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyy3hyach.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="nyy3hyach"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:information-circle" /></template>
