<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg5vvtsnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":215.696,"height":215.696,"left":20.152,"top":20.152};
const content = `<path class="vg5vvtsnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:general-translation-light" /></template>
