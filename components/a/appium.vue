<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbm41-n1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbm41-n1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:appium" /></template>
