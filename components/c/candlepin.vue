<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jb3y6ibjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jb3y6ibjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:candlepin" /></template>
