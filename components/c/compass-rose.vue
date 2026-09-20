<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4g1111yn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b4g1111yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:compass-rose" /></template>
