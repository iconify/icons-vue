<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mev0ftb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mev0ftb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bucket-circle-filled" /></template>
