<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lywu_-b-a.css';
import '../../css/j/j3_8dqerr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lywu_-b-a"/><path class="j3_8dqerr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:box-extra-large" /></template>
