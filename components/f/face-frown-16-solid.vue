<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp4ci8xgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rp4ci8xgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:face-frown-16-solid" /></template>
