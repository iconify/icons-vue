<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de49-_pzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de49-_pzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:homarr" /></template>
