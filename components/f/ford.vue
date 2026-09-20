<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzoba4bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rzoba4bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ford" /></template>
