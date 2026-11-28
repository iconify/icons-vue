<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld-u1jbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld-u1jbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:goal" /></template>
