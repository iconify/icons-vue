<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_txi0raq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_txi0raq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:bullet-point-expressive" /></template>
