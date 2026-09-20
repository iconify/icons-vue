<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzk0y1b8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzk0y1b8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-minus" /></template>
