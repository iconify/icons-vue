<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey4_sobig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ey4_sobig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:library-15" /></template>
