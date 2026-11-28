<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6r1e5d7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6r1e5d7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:face-angry" /></template>
