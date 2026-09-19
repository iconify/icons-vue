<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d49z1cc5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d49z1cc5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:compare" /></template>
