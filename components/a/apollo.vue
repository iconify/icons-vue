<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc3padctm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="bc3padctm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:apollo" /></template>
