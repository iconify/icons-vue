<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2n2hbb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2n2hbb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:google-home-2-bold" /></template>
