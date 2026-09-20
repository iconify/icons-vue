<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plbpu-ttj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plbpu-ttj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-fit-logo-solid" /></template>
