<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9i7bobei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="o9i7bobei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:garden-11" /></template>
