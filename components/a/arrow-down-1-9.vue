<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d78vz38qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="d78vz38qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down-1-9" /></template>
