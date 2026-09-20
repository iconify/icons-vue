<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u78s60hcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u78s60hcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:infuse-one-filled" /></template>
