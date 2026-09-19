<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coapld2vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="coapld2vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:folder" /></template>
