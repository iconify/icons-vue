<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlv8tnblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlv8tnblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:arm" /></template>
