<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu0vt1yam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu0vt1yam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:horizontal-top-right-main-light" /></template>
