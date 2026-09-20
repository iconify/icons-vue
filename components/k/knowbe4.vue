<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq9-xobpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":62.846,"height":60.485,"left":98.638,"top":11.193};
const content = `<path class="dq9-xobpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:knowbe4" /></template>
