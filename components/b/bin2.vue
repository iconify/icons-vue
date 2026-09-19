<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm2yf_bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fm2yf_bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:bin2" /></template>
