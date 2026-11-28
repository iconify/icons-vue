<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usr42ebpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usr42ebpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:lightbulb-star" /></template>
