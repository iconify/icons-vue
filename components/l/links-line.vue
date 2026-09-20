<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh5j824-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh5j824-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:links-line" /></template>
