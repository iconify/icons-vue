<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muybtqbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-6,"top":-6};
const content = `<path class="muybtqbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:background-color" /></template>
