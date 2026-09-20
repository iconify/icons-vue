<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw3hutb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zw3hutb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:details-block" /></template>
