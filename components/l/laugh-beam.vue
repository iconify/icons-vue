<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpeaxcgkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="jpeaxcgkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:laugh-beam" /></template>
