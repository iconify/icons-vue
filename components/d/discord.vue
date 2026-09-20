<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy2xg2bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy2xg2bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:discord" /></template>
