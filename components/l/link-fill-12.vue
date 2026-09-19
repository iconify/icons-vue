<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv_wzebzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gv_wzebzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:link-fill-12" /></template>
