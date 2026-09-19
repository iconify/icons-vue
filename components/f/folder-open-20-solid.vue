<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im8iwmb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="im8iwmb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:folder-open-20-solid" /></template>
