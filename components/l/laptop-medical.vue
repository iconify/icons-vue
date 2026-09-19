<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8v2597ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="r8v2597ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:laptop-medical" /></template>
