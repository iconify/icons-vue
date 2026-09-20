<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nlfp0n0lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlfp0n0lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kuma" /></template>
