<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zny7zrb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zny7zrb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:arrows-horizontal" /></template>
