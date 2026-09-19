<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_qscfbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c_qscfbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:laugh-beam" /></template>
