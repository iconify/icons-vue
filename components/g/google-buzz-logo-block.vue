<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv3r98bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv3r98bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:google-buzz-logo-block" /></template>
