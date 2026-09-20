<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfx2yfyho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfx2yfyho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gocd" /></template>
