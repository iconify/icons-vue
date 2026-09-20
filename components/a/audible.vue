<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwz12tbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwz12tbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:audible" /></template>
