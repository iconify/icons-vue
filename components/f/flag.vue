<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4w_g2sig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y4w_g2sig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:flag" /></template>
