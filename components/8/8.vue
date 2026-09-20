<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz_a4acti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zz_a4acti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:8" /></template>
