<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z93e_zjvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z93e_zjvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-up-fill-12" /></template>
