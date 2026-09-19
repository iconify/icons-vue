<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g41sx21jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g41sx21jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:earth" /></template>
