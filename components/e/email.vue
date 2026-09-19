<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sat31jbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sat31jbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:email" /></template>
