<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxc0iqbmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxc0iqbmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:container" /></template>
