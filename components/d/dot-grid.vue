<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj5h5m4vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yj5h5m4vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:dot-grid" /></template>
