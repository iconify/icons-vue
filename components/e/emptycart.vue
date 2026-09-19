<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cazfl1bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="cazfl1bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:emptycart" /></template>
