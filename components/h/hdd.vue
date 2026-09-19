<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_gr3j6ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_gr3j6ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:hdd" /></template>
