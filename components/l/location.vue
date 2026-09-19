<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3_f5bcdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j3_f5bcdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:location" /></template>
