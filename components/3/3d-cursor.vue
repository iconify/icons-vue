<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l322akb3h.css';
import '../../css/j/j6u729bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l322akb3h"/><path class="j6u729bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:3d-cursor" /></template>
