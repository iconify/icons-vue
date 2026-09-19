<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3he7ubvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i3he7ubvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cloud-arrow-up-16-solid" /></template>
