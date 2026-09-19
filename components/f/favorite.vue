<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oe555z8cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":962};
const content = `<path class="oe555z8cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:favorite" /></template>
