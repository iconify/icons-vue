<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoikssblk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":28};
const content = `<path class="qoikssblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fastwork" /></template>
