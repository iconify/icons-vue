<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udzsqrbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udzsqrbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:lightning-bolt-solid-expressive" /></template>
