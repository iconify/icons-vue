<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6r3vxmug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6r3vxmug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:email" /></template>
