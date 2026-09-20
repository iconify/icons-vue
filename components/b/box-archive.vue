<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfhpf1x0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gfhpf1x0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:box-archive" /></template>
