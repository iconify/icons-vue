<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr80_bo_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gr80_bo_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:hand-down" /></template>
