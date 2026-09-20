<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btpkolbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="btpkolbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:aviato" /></template>
