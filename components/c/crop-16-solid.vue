<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk2r7gbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sk2r7gbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:crop-16-solid" /></template>
