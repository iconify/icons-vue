<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1s7ofbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1s7ofbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:blender" /></template>
