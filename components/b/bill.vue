<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe1x-fbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe1x-fbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bill" /></template>
