<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddo1gnbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ddo1gnbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lock-rotation" /></template>
