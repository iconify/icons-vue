<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8379lkep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="h8379lkep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:eject" /></template>
