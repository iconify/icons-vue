<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us6b7-d0g.css';
import '../../css/p/p78ussb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="us6b7-d0g"/><path class="p78ussb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:battery-quarter" /></template>
