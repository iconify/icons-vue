<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv0asac4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="gv0asac4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:equal-square-fill" /></template>
