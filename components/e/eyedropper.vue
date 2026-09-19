<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9v9tbc3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="t9v9tbc3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:eyedropper" /></template>
