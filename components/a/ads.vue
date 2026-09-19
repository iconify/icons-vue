<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxf281bfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="lxf281bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:ads" /></template>
