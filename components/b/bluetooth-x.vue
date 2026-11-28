<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtg6whbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtg6whbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bluetooth-x" /></template>
