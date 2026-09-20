<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fws0xbbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fws0xbbna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dollar-sign" /></template>
