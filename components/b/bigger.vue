<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6zr5jbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i6zr5jbgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bigger" /></template>
