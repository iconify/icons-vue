<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yymv9fyfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yymv9fyfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-plus" /></template>
