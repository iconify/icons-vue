<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz72bebim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vz72bebim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:1-minus" /></template>
