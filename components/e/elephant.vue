<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zov604wmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zov604wmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:elephant" /></template>
