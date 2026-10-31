<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udzgqcbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="udzgqcbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cookie-16-solid" /></template>
