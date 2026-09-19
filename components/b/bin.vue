<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orf62jb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="orf62jb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bin" /></template>
