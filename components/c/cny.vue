<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3d6jdbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1408};
const content = `<path class="b3d6jdbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cny" /></template>
