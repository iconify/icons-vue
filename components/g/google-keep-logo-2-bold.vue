<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2eohmjnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2eohmjnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:google-keep-logo-2-bold" /></template>
