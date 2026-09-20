<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w01jywbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w01jywbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-stadia-logo-solid" /></template>
