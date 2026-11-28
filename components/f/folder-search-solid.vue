<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/andh5bc8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="andh5bc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:folder-search-solid" /></template>
