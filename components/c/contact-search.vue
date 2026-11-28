<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtor0hbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtor0hbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:contact-search" /></template>
