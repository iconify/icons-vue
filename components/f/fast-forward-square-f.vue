<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw-nk7zvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="cw-nk7zvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:fast-forward-square-f" /></template>
