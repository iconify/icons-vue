<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb0l32b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b mb0l32b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gestures" /></template>
