<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw5f-kbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xw5f-kbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calendar-16-solid" /></template>
