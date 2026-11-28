<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p37mgybgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p37mgybgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:folder-arrow-up-fill" /></template>
