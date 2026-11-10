<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0ysopb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p0ysopb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-x-mark-16-solid" /></template>
