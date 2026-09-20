<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppie82bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ppie82bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:equals" /></template>
