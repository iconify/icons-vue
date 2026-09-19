<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmy77ob3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmy77ob3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:cloud-download" /></template>
