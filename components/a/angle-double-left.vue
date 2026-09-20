<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz4bd4kev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz4bd4kev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:angle-double-left" /></template>
