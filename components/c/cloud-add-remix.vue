<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9i4nfbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d9i4nfbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:cloud-add-remix" /></template>
