<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0fpadcqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="d0fpadcqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:delete" /></template>
