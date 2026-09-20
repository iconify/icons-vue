<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2fm2ws7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x2fm2ws7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:css3-alt" /></template>
