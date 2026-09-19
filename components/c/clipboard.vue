<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlldb5b_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="mlldb5b_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:clipboard" /></template>
