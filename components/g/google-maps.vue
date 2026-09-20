<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky3l1lb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ky3l1lb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-maps" /></template>
