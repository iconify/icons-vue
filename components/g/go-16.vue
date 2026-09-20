<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thjka7p4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thjka7p4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:go-16" /></template>
