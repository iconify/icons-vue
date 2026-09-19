<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkca6ac2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="rkca6ac2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:cog-alt" /></template>
