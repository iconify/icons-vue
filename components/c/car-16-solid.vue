<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de-l4_xse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="de-l4_xse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:car-16-solid" /></template>
