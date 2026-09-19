<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppty-ybvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":961};
const content = `<path class="ppty-ybvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:lighton" /></template>
