<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxtm2eikw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="mxtm2eikw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-circle-down" /></template>
