<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1crm4r6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f1crm4r6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:diamond-one" /></template>
