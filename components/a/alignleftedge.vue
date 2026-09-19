<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f35lyobeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="f35lyobeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alignleftedge" /></template>
