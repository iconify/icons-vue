<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlmj3cc4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlmj3cc4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:digitalocean" /></template>
