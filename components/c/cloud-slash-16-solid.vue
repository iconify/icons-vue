<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzwn0bbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lzwn0bbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-slash-16-solid" /></template>
