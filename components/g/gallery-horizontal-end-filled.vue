<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y79pc66rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y79pc66rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:gallery-horizontal-end-filled" /></template>
