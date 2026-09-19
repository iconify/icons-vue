<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7_ns-bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7_ns-bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-americas" /></template>
