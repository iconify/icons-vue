<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-21fi9kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-21fi9kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:folder" /></template>
