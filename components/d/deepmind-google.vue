<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqi4lmbxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqi4lmbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deepmind-google" /></template>
