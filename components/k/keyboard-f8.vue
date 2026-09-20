<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z27h5bbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z27h5bbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-f8" /></template>
