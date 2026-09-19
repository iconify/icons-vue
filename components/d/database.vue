<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5hr-mbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="d5hr-mbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:database" /></template>
