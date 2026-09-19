<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lji0e9b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lji0e9b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:folder-arrow-up" /></template>
