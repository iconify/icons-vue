<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xti4taclw.css';
import '../../css/p/pr5hkx2sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xti4taclw"/><path class="pr5hkx2sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:c-sharp" /></template>
