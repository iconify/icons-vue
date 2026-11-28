<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzznv0gvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzznv0gvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:headphones" /></template>
