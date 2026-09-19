<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-kcr6bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w-kcr6bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:folder" /></template>
