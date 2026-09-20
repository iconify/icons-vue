<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2_63yb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2_63yb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-alt" /></template>
