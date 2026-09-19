<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9l3vac1v.css';
import '../../css/x/x8lyhp39e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i9l3vac1v"/><path class="x8lyhp39e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cz" /></template>
