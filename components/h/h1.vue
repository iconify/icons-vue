<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdq-wdb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdq-wdb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:h1" /></template>
