<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbpx2jbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mbpx2jbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:backward2" /></template>
