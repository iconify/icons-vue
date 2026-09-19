<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ji56rccna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ji56rccna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:fonts" /></template>
