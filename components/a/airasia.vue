<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh-317bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh-317bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:airasia" /></template>
