<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjyx39bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="zjyx39bvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-holding-heart" /></template>
